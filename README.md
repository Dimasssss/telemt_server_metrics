# Server Metrics 2026-03-11 14:10:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 85413.0 (23h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2046048
telemt_connections_bad_total 29984
telemt_handshake_timeouts_total 51956
telemt_upstream_connect_attempt_total 17930
telemt_upstream_connect_success_total 17919
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 17930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8775
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 3955
telemt_me_reconnect_attempts_total 26454
telemt_me_reconnect_success_total 13615
telemt_me_reader_eof_total 14670
telemt_me_idle_close_by_peer_total 14670
telemt_me_route_drop_no_conn_total 753869
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1870520
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9845
telemt_desync_full_logged_total 2666
telemt_desync_suppressed_total 7179
telemt_desync_frames_bucket_total{bucket="1_2"} 2436
telemt_desync_frames_bucket_total{bucket="3_10"} 3813
telemt_desync_frames_bucket_total{bucket="gt_10"} 3596
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14164
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 13609
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 549
telemt_user_connections_total{user="hello"} 1869024
telemt_user_connections_current{user="hello"} 1552
telemt_user_octets_from_client{user="hello"} 25137845344 (23.41 GB)
telemt_user_octets_to_client{user="hello"} 531857506496 (495.33 GB)
telemt_user_unique_ips_current{user="hello"} 405
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 85469.6 (23h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 769654
telemt_connections_bad_total 13107
telemt_handshake_timeouts_total 52083
telemt_upstream_connect_attempt_total 27432
telemt_upstream_connect_success_total 24483
telemt_upstream_connect_fail_total 2949
telemt_upstream_connect_attempts_per_request{bucket="1"} 27432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10922
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2949
telemt_me_keepalive_timeout_total 2521
telemt_me_reconnect_attempts_total 19348
telemt_me_reconnect_success_total 17265
telemt_me_reader_eof_total 18275
telemt_me_idle_close_by_peer_total 18272
telemt_me_route_drop_no_conn_total 301208
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 651341
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2819
telemt_desync_full_logged_total 893
telemt_desync_suppressed_total 1926
telemt_desync_frames_bucket_total{bucket="1_2"} 874
telemt_desync_frames_bucket_total{bucket="3_10"} 1025
telemt_desync_frames_bucket_total{bucket="gt_10"} 920
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 17520
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 17242
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 653828
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 6952381514 (6.47 GB)
telemt_user_octets_to_client{user="hello"} 184937480220 (172.24 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 85469.6 (23h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1332198
telemt_connections_bad_total 8419
telemt_handshake_timeouts_total 121211
telemt_upstream_connect_attempt_total 22735
telemt_upstream_connect_success_total 22464
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 22735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 903
telemt_me_reconnect_attempts_total 33208
telemt_me_reconnect_success_total 17098
telemt_me_reader_eof_total 18370
telemt_me_idle_close_by_peer_total 18370
telemt_me_route_drop_no_conn_total 480223
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1153353
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3065
telemt_desync_full_logged_total 908
telemt_desync_suppressed_total 2157
telemt_desync_frames_bucket_total{bucket="1_2"} 735
telemt_desync_frames_bucket_total{bucket="3_10"} 1161
telemt_desync_frames_bucket_total{bucket="gt_10"} 1169
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 17828
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 17087
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 730
telemt_user_connections_total{user="hello"} 1153156
telemt_user_connections_current{user="hello"} 921
telemt_user_octets_from_client{user="hello"} 13897547813 (12.94 GB)
telemt_user_octets_to_client{user="hello"} 344114883085 (320.48 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 85470.0 (23h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 956114
telemt_connections_bad_total 77271
telemt_handshake_timeouts_total 90319
telemt_upstream_connect_attempt_total 23143
telemt_upstream_connect_success_total 23143
telemt_upstream_connect_attempts_per_request{bucket="1"} 23143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 951
telemt_me_reconnect_attempts_total 19961
telemt_me_reconnect_success_total 18890
telemt_me_reader_eof_total 20034
telemt_me_idle_close_by_peer_total 20033
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 309861
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 762585
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1619
telemt_desync_full_logged_total 634
telemt_desync_suppressed_total 985
telemt_desync_frames_bucket_total{bucket="1_2"} 586
telemt_desync_frames_bucket_total{bucket="3_10"} 568
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 19124
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 18862
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 761935
telemt_user_connections_current{user="hello"} 591
telemt_user_octets_from_client{user="hello"} 8867181000 (8.26 GB)
telemt_user_octets_to_client{user="hello"} 220818142520 (205.65 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 85469.7 (23h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1049211
telemt_connections_bad_total 6826
telemt_handshake_timeouts_total 9658
telemt_upstream_connect_attempt_total 23109
telemt_upstream_connect_success_total 23009
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 23109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11022
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 185
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 989
telemt_me_reconnect_attempts_total 22702
telemt_me_reconnect_success_total 18628
telemt_me_reader_eof_total 19658
telemt_me_idle_close_by_peer_total 19658
telemt_me_route_drop_no_conn_total 372484
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 953015
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3770
telemt_desync_full_logged_total 1389
telemt_desync_suppressed_total 2381
telemt_desync_frames_bucket_total{bucket="1_2"} 1321
telemt_desync_frames_bucket_total{bucket="3_10"} 1418
telemt_desync_frames_bucket_total{bucket="gt_10"} 1031
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18994
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 18628
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 366
telemt_user_connections_total{user="hello"} 952752
telemt_user_connections_current{user="hello"} 730
telemt_user_octets_from_client{user="hello"} 13807117743 (12.86 GB)
telemt_user_octets_to_client{user="hello"} 336328933898 (313.23 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 141
```