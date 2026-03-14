# Server Metrics 2026-03-14 09:59:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 187267.9 (52h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5356203
telemt_connections_bad_total 52481
telemt_handshake_timeouts_total 119648
telemt_upstream_connect_attempt_total 39249
telemt_upstream_connect_success_total 38994
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 39249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17691
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_keepalive_timeout_total 7539
telemt_me_reconnect_attempts_total 38578
telemt_me_reconnect_success_total 27362
telemt_me_reader_eof_total 29348
telemt_me_idle_close_by_peer_total 29347
telemt_me_route_drop_no_conn_total 2024302
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4907699
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18760
telemt_desync_full_logged_total 5127
telemt_desync_suppressed_total 13633
telemt_desync_frames_bucket_total{bucket="1_2"} 4596
telemt_desync_frames_bucket_total{bucket="3_10"} 7166
telemt_desync_frames_bucket_total{bucket="gt_10"} 6998
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 28113
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 27349
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 751
telemt_user_connections_total{user="hello"} 4909144
telemt_user_connections_current{user="hello"} 1721
telemt_user_octets_from_client{user="hello"} 75102935568 (69.95 GB)
telemt_user_octets_to_client{user="hello"} 1565940394293 (1.42 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 86931.8 (24h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 976150
telemt_connections_bad_total 56128
telemt_handshake_timeouts_total 20906
telemt_upstream_connect_attempt_total 22895
telemt_upstream_connect_success_total 22605
telemt_upstream_connect_fail_total 290
telemt_upstream_connect_attempts_per_request{bucket="1"} 22895
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10040
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 251
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 290
telemt_me_keepalive_timeout_total 2231
telemt_me_reconnect_attempts_total 26122
telemt_me_reconnect_success_total 16249
telemt_me_reader_eof_total 17427
telemt_me_idle_close_by_peer_total 17426
telemt_me_route_drop_no_conn_total 327260
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 795805
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2231
telemt_desync_full_logged_total 703
telemt_desync_suppressed_total 1528
telemt_desync_frames_bucket_total{bucket="1_2"} 509
telemt_desync_frames_bucket_total{bucket="3_10"} 954
telemt_desync_frames_bucket_total{bucket="gt_10"} 768
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 16789
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 16241
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 540
telemt_user_connections_total{user="hello"} 797701
telemt_user_connections_current{user="hello"} 759
telemt_user_octets_from_client{user="hello"} 8655884773 (8.06 GB)
telemt_user_octets_to_client{user="hello"} 275667037480 (256.73 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 216888.4 (60h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3811127
telemt_connections_bad_total 45050
telemt_handshake_timeouts_total 251946
telemt_upstream_connect_attempt_total 48879
telemt_upstream_connect_success_total 48858
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 48879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22796
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 249
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10914
telemt_me_reconnect_attempts_total 42766
telemt_me_reconnect_success_total 37769
telemt_me_reader_eof_total 40102
telemt_me_idle_close_by_peer_total 40101
telemt_me_route_drop_no_conn_total 1308995
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3183897
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10269
telemt_desync_full_logged_total 3490
telemt_desync_suppressed_total 6779
telemt_desync_frames_bucket_total{bucket="1_2"} 1850
telemt_desync_frames_bucket_total{bucket="3_10"} 3717
telemt_desync_frames_bucket_total{bucket="gt_10"} 4702
telemt_pool_swap_total 203
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 38292
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 37728
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 3183063
telemt_user_connections_current{user="hello"} 908
telemt_user_octets_from_client{user="hello"} 53783442336 (50.09 GB)
telemt_user_octets_to_client{user="hello"} 1140486548457 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 216891.0 (60h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2517440
telemt_connections_bad_total 23404
telemt_handshake_timeouts_total 317197
telemt_upstream_connect_attempt_total 67089
telemt_upstream_connect_success_total 64587
telemt_upstream_connect_fail_total 2365
telemt_upstream_connect_attempts_per_request{bucket="1"} 66815
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2364
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20654
telemt_me_reconnect_attempts_total 58442
telemt_me_reconnect_success_total 46790
telemt_me_reader_eof_total 50150
telemt_me_idle_close_by_peer_total 50143
telemt_me_route_drop_no_conn_total 840932
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1972058
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4043
telemt_desync_full_logged_total 1321
telemt_desync_suppressed_total 2722
telemt_desync_frames_bucket_total{bucket="1_2"} 1138
telemt_desync_frames_bucket_total{bucket="3_10"} 1653
telemt_desync_frames_bucket_total{bucket="gt_10"} 1252
telemt_pool_swap_total 188
telemt_me_writer_removed_unexpected_total 47559
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 46766
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 769
telemt_user_connections_total{user="hello"} 1978241
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 29501037575 (27.47 GB)
telemt_user_octets_to_client{user="hello"} 714370136562 (665.31 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 86324.2 (23h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 961123
telemt_connections_bad_total 15095
telemt_handshake_timeouts_total 12569
telemt_upstream_connect_attempt_total 21802
telemt_upstream_connect_success_total 21217
telemt_upstream_connect_fail_total 585
telemt_upstream_connect_attempts_per_request{bucket="1"} 21802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11075
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 585
telemt_me_keepalive_timeout_total 1683
telemt_me_reconnect_attempts_total 71051
telemt_me_reconnect_success_total 16927
telemt_me_reader_eof_total 19030
telemt_me_idle_close_by_peer_total 19029
telemt_me_route_drop_no_conn_total 367389
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 890807
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2339
telemt_desync_full_logged_total 733
telemt_desync_suppressed_total 1606
telemt_desync_frames_bucket_total{bucket="1_2"} 783
telemt_desync_frames_bucket_total{bucket="3_10"} 875
telemt_desync_frames_bucket_total{bucket="gt_10"} 681
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 18776
telemt_me_refill_failed_total 1686
telemt_me_writer_restored_same_endpoint_total 16922
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1849
telemt_user_connections_total{user="hello"} 890752
telemt_user_connections_current{user="hello"} 677
telemt_user_octets_from_client{user="hello"} 15750610260 (14.67 GB)
telemt_user_octets_to_client{user="hello"} 298684462876 (278.17 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 84
```