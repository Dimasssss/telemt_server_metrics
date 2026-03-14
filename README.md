# Server Metrics 2026-03-14 12:58:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 198007.8 (55h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5760958
telemt_connections_bad_total 66117
telemt_handshake_timeouts_total 127181
telemt_upstream_connect_attempt_total 41474
telemt_upstream_connect_success_total 41208
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 41474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18722
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 7869
telemt_me_reconnect_attempts_total 47976
telemt_me_reconnect_success_total 29039
telemt_me_reader_eof_total 31303
telemt_me_idle_close_by_peer_total 31302
telemt_me_route_drop_no_conn_total 2183947
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5281431
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20398
telemt_desync_full_logged_total 5589
telemt_desync_suppressed_total 14809
telemt_desync_frames_bucket_total{bucket="1_2"} 4904
telemt_desync_frames_bucket_total{bucket="3_10"} 7747
telemt_desync_frames_bucket_total{bucket="gt_10"} 7747
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 30052
telemt_me_refill_failed_total 586
telemt_me_writer_restored_same_endpoint_total 29026
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 1013
telemt_user_connections_total{user="hello"} 5283048
telemt_user_connections_current{user="hello"} 1818
telemt_user_octets_from_client{user="hello"} 82441298196 (76.78 GB)
telemt_user_octets_to_client{user="hello"} 1683052743477 (1.53 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 487
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 97671.5 (27h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1130391
telemt_connections_bad_total 59157
telemt_handshake_timeouts_total 27157
telemt_upstream_connect_attempt_total 24769
telemt_upstream_connect_success_total 24461
telemt_upstream_connect_fail_total 308
telemt_upstream_connect_attempts_per_request{bucket="1"} 24769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 265
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 308
telemt_me_keepalive_timeout_total 2437
telemt_me_reconnect_attempts_total 39346
telemt_me_reconnect_success_total 17560
telemt_me_reader_eof_total 19133
telemt_me_idle_close_by_peer_total 19132
telemt_me_route_drop_no_conn_total 382633
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 932311
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2606
telemt_desync_full_logged_total 819
telemt_desync_suppressed_total 1787
telemt_desync_frames_bucket_total{bucket="1_2"} 677
telemt_desync_frames_bucket_total{bucket="3_10"} 1090
telemt_desync_frames_bucket_total{bucket="gt_10"} 839
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18489
telemt_me_refill_failed_total 674
telemt_me_writer_restored_same_endpoint_total 17552
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 929
telemt_user_connections_total{user="hello"} 934220
telemt_user_connections_current{user="hello"} 560
telemt_user_octets_from_client{user="hello"} 10311346477 (9.60 GB)
telemt_user_octets_to_client{user="hello"} 333704958636 (310.79 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 227628.2 (63h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4085932
telemt_connections_bad_total 46702
telemt_handshake_timeouts_total 284687
telemt_upstream_connect_attempt_total 51259
telemt_upstream_connect_success_total 51237
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 51259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23926
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 263
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 11354
telemt_me_reconnect_attempts_total 45597
telemt_me_reconnect_success_total 39588
telemt_me_reader_eof_total 42032
telemt_me_idle_close_by_peer_total 42030
telemt_me_route_drop_no_conn_total 1403906
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3416951
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10917
telemt_desync_full_logged_total 3686
telemt_desync_suppressed_total 7231
telemt_desync_frames_bucket_total{bucket="1_2"} 2005
telemt_desync_frames_bucket_total{bucket="3_10"} 3933
telemt_desync_frames_bucket_total{bucket="gt_10"} 4979
telemt_pool_swap_total 209
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 40174
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 39547
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 586
telemt_user_connections_total{user="hello"} 3416088
telemt_user_connections_current{user="hello"} 1034
telemt_user_octets_from_client{user="hello"} 58220357548 (54.22 GB)
telemt_user_octets_to_client{user="hello"} 1217462523137 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 227630.8 (63h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2661474
telemt_connections_bad_total 23525
telemt_handshake_timeouts_total 347478
telemt_upstream_connect_attempt_total 69990
telemt_upstream_connect_success_total 67480
telemt_upstream_connect_fail_total 2373
telemt_upstream_connect_attempts_per_request{bucket="1"} 69716
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2372
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 21010
telemt_me_reconnect_attempts_total 61920
telemt_me_reconnect_success_total 49135
telemt_me_reader_eof_total 52638
telemt_me_idle_close_by_peer_total 52630
telemt_me_route_drop_no_conn_total 881319
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2077644
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4117
telemt_desync_full_logged_total 1355
telemt_desync_suppressed_total 2762
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 1683
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 195
telemt_me_writer_removed_unexpected_total 49965
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 49110
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 830
telemt_user_connections_total{user="hello"} 2084213
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 30810570791 (28.69 GB)
telemt_user_octets_to_client{user="hello"} 740146704234 (689.32 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 97064.4 (26h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1117301
telemt_connections_bad_total 18175
telemt_handshake_timeouts_total 14262
telemt_upstream_connect_attempt_total 23112
telemt_upstream_connect_success_total 22452
telemt_upstream_connect_fail_total 660
telemt_upstream_connect_attempts_per_request{bucket="1"} 23112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11659
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 660
telemt_me_keepalive_timeout_total 1820
telemt_me_reconnect_attempts_total 88168
telemt_me_reconnect_success_total 17626
telemt_me_reader_eof_total 20238
telemt_me_idle_close_by_peer_total 20237
telemt_me_route_drop_no_conn_total 450041
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1035205
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2742
telemt_desync_full_logged_total 862
telemt_desync_suppressed_total 1880
telemt_desync_frames_bucket_total{bucket="1_2"} 997
telemt_desync_frames_bucket_total{bucket="3_10"} 959
telemt_desync_frames_bucket_total{bucket="gt_10"} 786
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19989
telemt_me_refill_failed_total 2199
telemt_me_writer_restored_same_endpoint_total 17621
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2363
telemt_user_connections_total{user="hello"} 1034390
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 18029259740 (16.79 GB)
telemt_user_octets_to_client{user="hello"} 349271039464 (325.28 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 86
```