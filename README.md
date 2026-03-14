# Server Metrics 2026-03-14 09:54:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 186961.3 (51h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5343178
telemt_connections_bad_total 51639
telemt_handshake_timeouts_total 119490
telemt_upstream_connect_attempt_total 39200
telemt_upstream_connect_success_total 38945
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 39200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_keepalive_timeout_total 7538
telemt_me_reconnect_attempts_total 38541
telemt_me_reconnect_success_total 27325
telemt_me_reader_eof_total 29311
telemt_me_idle_close_by_peer_total 29310
telemt_me_route_drop_no_conn_total 2019852
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4896561
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18731
telemt_desync_full_logged_total 5115
telemt_desync_suppressed_total 13616
telemt_desync_frames_bucket_total{bucket="1_2"} 4593
telemt_desync_frames_bucket_total{bucket="3_10"} 7157
telemt_desync_frames_bucket_total{bucket="gt_10"} 6981
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 28076
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 27312
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 751
telemt_user_connections_total{user="hello"} 4898018
telemt_user_connections_current{user="hello"} 1602
telemt_user_octets_from_client{user="hello"} 74950616320 (69.80 GB)
telemt_user_octets_to_client{user="hello"} 1562970602913 (1.42 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 86625.0 (24h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 971801
telemt_connections_bad_total 55879
telemt_handshake_timeouts_total 20755
telemt_upstream_connect_attempt_total 22843
telemt_upstream_connect_success_total 22553
telemt_upstream_connect_fail_total 290
telemt_upstream_connect_attempts_per_request{bucket="1"} 22843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10013
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 250
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 290
telemt_me_keepalive_timeout_total 2226
telemt_me_reconnect_attempts_total 26070
telemt_me_reconnect_success_total 16197
telemt_me_reader_eof_total 17375
telemt_me_idle_close_by_peer_total 17374
telemt_me_route_drop_no_conn_total 325151
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 791964
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2227
telemt_desync_full_logged_total 700
telemt_desync_suppressed_total 1527
telemt_desync_frames_bucket_total{bucket="1_2"} 506
telemt_desync_frames_bucket_total{bucket="3_10"} 954
telemt_desync_frames_bucket_total{bucket="gt_10"} 767
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 16737
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 16189
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 540
telemt_user_connections_total{user="hello"} 793860
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 8624023725 (8.03 GB)
telemt_user_octets_to_client{user="hello"} 274401900484 (255.56 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 216581.8 (60h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3802618
telemt_connections_bad_total 44699
telemt_handshake_timeouts_total 251373
telemt_upstream_connect_attempt_total 48849
telemt_upstream_connect_success_total 48828
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 48849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22782
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 249
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10911
telemt_me_reconnect_attempts_total 42736
telemt_me_reconnect_success_total 37739
telemt_me_reader_eof_total 40072
telemt_me_idle_close_by_peer_total 40071
telemt_me_route_drop_no_conn_total 1306685
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3177511
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10251
telemt_desync_full_logged_total 3485
telemt_desync_suppressed_total 6766
telemt_desync_frames_bucket_total{bucket="1_2"} 1844
telemt_desync_frames_bucket_total{bucket="3_10"} 3711
telemt_desync_frames_bucket_total{bucket="gt_10"} 4696
telemt_pool_swap_total 203
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 38262
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 37698
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 3176680
telemt_user_connections_current{user="hello"} 872
telemt_user_octets_from_client{user="hello"} 53689928524 (50.00 GB)
telemt_user_octets_to_client{user="hello"} 1138714607609 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 216584.3 (60h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2512750
telemt_connections_bad_total 23403
telemt_handshake_timeouts_total 316151
telemt_upstream_connect_attempt_total 67022
telemt_upstream_connect_success_total 64520
telemt_upstream_connect_fail_total 2365
telemt_upstream_connect_attempts_per_request{bucket="1"} 66748
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25841
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2364
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20647
telemt_me_reconnect_attempts_total 58375
telemt_me_reconnect_success_total 46723
telemt_me_reader_eof_total 50083
telemt_me_idle_close_by_peer_total 50076
telemt_me_route_drop_no_conn_total 840042
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1968697
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
telemt_me_writer_removed_unexpected_total 47492
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 46699
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 769
telemt_user_connections_total{user="hello"} 1974879
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 29485512507 (27.46 GB)
telemt_user_octets_to_client{user="hello"} 713654451910 (664.64 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 86018.1 (23h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 956437
telemt_connections_bad_total 14860
telemt_handshake_timeouts_total 12505
telemt_upstream_connect_attempt_total 21762
telemt_upstream_connect_success_total 21177
telemt_upstream_connect_fail_total 585
telemt_upstream_connect_attempts_per_request{bucket="1"} 21762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11051
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 585
telemt_me_keepalive_timeout_total 1683
telemt_me_reconnect_attempts_total 71011
telemt_me_reconnect_success_total 16887
telemt_me_reader_eof_total 18988
telemt_me_idle_close_by_peer_total 18987
telemt_me_route_drop_no_conn_total 365584
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 886587
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2332
telemt_desync_full_logged_total 731
telemt_desync_suppressed_total 1601
telemt_desync_frames_bucket_total{bucket="1_2"} 777
telemt_desync_frames_bucket_total{bucket="3_10"} 874
telemt_desync_frames_bucket_total{bucket="gt_10"} 681
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 18734
telemt_me_refill_failed_total 1686
telemt_me_writer_restored_same_endpoint_total 16882
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1847
telemt_user_connections_total{user="hello"} 886532
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 15704608500 (14.63 GB)
telemt_user_octets_to_client{user="hello"} 297054929908 (276.65 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 96
```