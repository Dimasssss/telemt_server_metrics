# Server Metrics 2026-03-14 09:39:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 186040.7 (51h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5308657
telemt_connections_bad_total 50563
telemt_handshake_timeouts_total 118733
telemt_upstream_connect_attempt_total 38996
telemt_upstream_connect_success_total 38744
telemt_upstream_connect_fail_total 252
telemt_upstream_connect_attempts_per_request{bucket="1"} 38996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17584
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 252
telemt_me_keepalive_timeout_total 7536
telemt_me_reconnect_attempts_total 38384
telemt_me_reconnect_success_total 27169
telemt_me_reader_eof_total 29153
telemt_me_idle_close_by_peer_total 29152
telemt_me_route_drop_no_conn_total 2006864
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4864622
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18623
telemt_desync_full_logged_total 5088
telemt_desync_suppressed_total 13535
telemt_desync_frames_bucket_total{bucket="1_2"} 4580
telemt_desync_frames_bucket_total{bucket="3_10"} 7103
telemt_desync_frames_bucket_total{bucket="gt_10"} 6940
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 27917
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 27156
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 748
telemt_user_connections_total{user="hello"} 4866096
telemt_user_connections_current{user="hello"} 1654
telemt_user_octets_from_client{user="hello"} 74624825040 (69.50 GB)
telemt_user_octets_to_client{user="hello"} 1553976935305 (1.41 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 459
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 85704.7 (23h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 958194
telemt_connections_bad_total 55140
telemt_handshake_timeouts_total 19792
telemt_upstream_connect_attempt_total 22679
telemt_upstream_connect_success_total 22390
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 22679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9929
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 247
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_keepalive_timeout_total 2218
telemt_me_reconnect_attempts_total 25950
telemt_me_reconnect_success_total 16079
telemt_me_reader_eof_total 17247
telemt_me_idle_close_by_peer_total 17246
telemt_me_route_drop_no_conn_total 320107
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 780436
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2184
telemt_desync_full_logged_total 688
telemt_desync_suppressed_total 1496
telemt_desync_frames_bucket_total{bucket="1_2"} 496
telemt_desync_frames_bucket_total{bucket="3_10"} 937
telemt_desync_frames_bucket_total{bucket="gt_10"} 751
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 16616
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 16071
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 782333
telemt_user_connections_current{user="hello"} 667
telemt_user_octets_from_client{user="hello"} 8302568393 (7.73 GB)
telemt_user_octets_to_client{user="hello"} 269902504560 (251.37 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 215661.1 (59h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3779738
telemt_connections_bad_total 44534
telemt_handshake_timeouts_total 249553
telemt_upstream_connect_attempt_total 48670
telemt_upstream_connect_success_total 48649
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 48670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22698
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 248
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10909
telemt_me_reconnect_attempts_total 42600
telemt_me_reconnect_success_total 37604
telemt_me_reader_eof_total 39929
telemt_me_idle_close_by_peer_total 39928
telemt_me_route_drop_no_conn_total 1299207
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3157510
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10190
telemt_desync_full_logged_total 3463
telemt_desync_suppressed_total 6727
telemt_desync_frames_bucket_total{bucket="1_2"} 1825
telemt_desync_frames_bucket_total{bucket="3_10"} 3697
telemt_desync_frames_bucket_total{bucket="gt_10"} 4668
telemt_pool_swap_total 202
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 38127
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 37563
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 3156683
telemt_user_connections_current{user="hello"} 919
telemt_user_octets_from_client{user="hello"} 53442203584 (49.77 GB)
telemt_user_octets_to_client{user="hello"} 1131515876769 (1.03 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 215663.8 (59h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2498520
telemt_connections_bad_total 23381
telemt_handshake_timeouts_total 311572
telemt_upstream_connect_attempt_total 66769
telemt_upstream_connect_success_total 64270
telemt_upstream_connect_fail_total 2362
telemt_upstream_connect_attempts_per_request{bucket="1"} 66495
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25738
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2361
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20644
telemt_me_reconnect_attempts_total 58169
telemt_me_reconnect_success_total 46518
telemt_me_reader_eof_total 49873
telemt_me_idle_close_by_peer_total 49866
telemt_me_route_drop_no_conn_total 836715
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1959880
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4025
telemt_desync_full_logged_total 1317
telemt_desync_suppressed_total 2708
telemt_desync_frames_bucket_total{bucket="1_2"} 1131
telemt_desync_frames_bucket_total{bucket="3_10"} 1645
telemt_desync_frames_bucket_total{bucket="gt_10"} 1249
telemt_pool_swap_total 188
telemt_me_writer_removed_unexpected_total 47282
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 46494
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 764
telemt_user_connections_total{user="hello"} 1966061
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 29404188439 (27.38 GB)
telemt_user_octets_to_client{user="hello"} 710293947274 (661.51 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 85097.4 (23h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 942862
telemt_connections_bad_total 14069
telemt_handshake_timeouts_total 12311
telemt_upstream_connect_attempt_total 21570
telemt_upstream_connect_success_total 20992
telemt_upstream_connect_fail_total 578
telemt_upstream_connect_attempts_per_request{bucket="1"} 21570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10942
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 578
telemt_me_keepalive_timeout_total 1681
telemt_me_reconnect_attempts_total 69526
telemt_me_reconnect_success_total 16747
telemt_me_reader_eof_total 18805
telemt_me_idle_close_by_peer_total 18804
telemt_me_route_drop_no_conn_total 361126
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 874793
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2319
telemt_desync_full_logged_total 723
telemt_desync_suppressed_total 1596
telemt_desync_frames_bucket_total{bucket="1_2"} 769
telemt_desync_frames_bucket_total{bucket="3_10"} 871
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 18551
telemt_me_refill_failed_total 1644
telemt_me_writer_restored_same_endpoint_total 16742
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1804
telemt_user_connections_total{user="hello"} 874738
telemt_user_connections_current{user="hello"} 706
telemt_user_octets_from_client{user="hello"} 15568531280 (14.50 GB)
telemt_user_octets_to_client{user="hello"} 294399835632 (274.18 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 96
```