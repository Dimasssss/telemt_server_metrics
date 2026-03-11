# Server Metrics 2026-03-11 08:54:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 66427.3 (18h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1387850
telemt_connections_bad_total 15747
telemt_handshake_timeouts_total 40226
telemt_upstream_connect_attempt_total 13842
telemt_upstream_connect_success_total 13833
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 13842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 757
telemt_me_reconnect_attempts_total 22171
telemt_me_reconnect_success_total 10485
telemt_me_reader_eof_total 11352
telemt_me_idle_close_by_peer_total 11352
telemt_me_route_drop_no_conn_total 510081
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1258143
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6161
telemt_desync_full_logged_total 1708
telemt_desync_suppressed_total 4453
telemt_desync_frames_bucket_total{bucket="1_2"} 1621
telemt_desync_frames_bucket_total{bucket="3_10"} 2336
telemt_desync_frames_bucket_total{bucket="gt_10"} 2204
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10951
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10479
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 1257812
telemt_user_connections_current{user="hello"} 1344
telemt_user_octets_from_client{user="hello"} 16704247244 (15.56 GB)
telemt_user_octets_to_client{user="hello"} 363196059128 (338.25 GB)
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 66484.2 (18h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 536134
telemt_connections_bad_total 9094
telemt_handshake_timeouts_total 29698
telemt_upstream_connect_attempt_total 22772
telemt_upstream_connect_success_total 19846
telemt_upstream_connect_fail_total 2926
telemt_upstream_connect_attempts_per_request{bucket="1"} 22772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8590
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2926
telemt_me_keepalive_timeout_total 2064
telemt_me_reconnect_attempts_total 14416
telemt_me_reconnect_success_total 13584
telemt_me_reader_eof_total 14373
telemt_me_idle_close_by_peer_total 14371
telemt_me_route_drop_no_conn_total 226059
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 454094
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2142
telemt_desync_full_logged_total 657
telemt_desync_suppressed_total 1485
telemt_desync_frames_bucket_total{bucket="1_2"} 714
telemt_desync_frames_bucket_total{bucket="3_10"} 770
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 13742
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13562
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 456334
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 4435016458 (4.13 GB)
telemt_user_octets_to_client{user="hello"} 121864082104 (113.49 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 66484.0 (18h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 922925
telemt_connections_bad_total 7245
telemt_handshake_timeouts_total 77388
telemt_upstream_connect_attempt_total 17901
telemt_upstream_connect_success_total 17682
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 17901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 756
telemt_me_reconnect_attempts_total 25652
telemt_me_reconnect_success_total 13291
telemt_me_reader_eof_total 14301
telemt_me_idle_close_by_peer_total 14301
telemt_me_route_drop_no_conn_total 304679
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 800421
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2292
telemt_desync_full_logged_total 680
telemt_desync_suppressed_total 1612
telemt_desync_frames_bucket_total{bucket="1_2"} 550
telemt_desync_frames_bucket_total{bucket="3_10"} 835
telemt_desync_frames_bucket_total{bucket="gt_10"} 907
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 13846
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 13280
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 555
telemt_user_connections_total{user="hello"} 801225
telemt_user_connections_current{user="hello"} 724
telemt_user_octets_from_client{user="hello"} 9502649325 (8.85 GB)
telemt_user_octets_to_client{user="hello"} 241663339245 (225.07 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 66484.6 (18h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 683875
telemt_connections_bad_total 62231
telemt_handshake_timeouts_total 66929
telemt_upstream_connect_attempt_total 18359
telemt_upstream_connect_success_total 18359
telemt_upstream_connect_attempts_per_request{bucket="1"} 18359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 691
telemt_me_reconnect_attempts_total 16102
telemt_me_reconnect_success_total 15049
telemt_me_reader_eof_total 15986
telemt_me_idle_close_by_peer_total 15985
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 212361
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 533325
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1238
telemt_desync_full_logged_total 466
telemt_desync_suppressed_total 772
telemt_desync_frames_bucket_total{bucket="1_2"} 412
telemt_desync_frames_bucket_total{bucket="3_10"} 469
telemt_desync_frames_bucket_total{bucket="gt_10"} 357
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 15226
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 15027
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 532700
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 6266437316 (5.84 GB)
telemt_user_octets_to_client{user="hello"} 150459054676 (140.13 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 66484.1 (18h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 722748
telemt_connections_bad_total 5982
telemt_handshake_timeouts_total 6780
telemt_upstream_connect_attempt_total 18188
telemt_upstream_connect_success_total 18115
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 18188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 733
telemt_me_reconnect_attempts_total 18480
telemt_me_reconnect_success_total 14689
telemt_me_reader_eof_total 15528
telemt_me_idle_close_by_peer_total 15528
telemt_me_route_drop_no_conn_total 244181
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 655689
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2858
telemt_desync_full_logged_total 1079
telemt_desync_suppressed_total 1779
telemt_desync_frames_bucket_total{bucket="1_2"} 1001
telemt_desync_frames_bucket_total{bucket="3_10"} 1186
telemt_desync_frames_bucket_total{bucket="gt_10"} 671
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 14993
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14689
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 655376
telemt_user_connections_current{user="hello"} 695
telemt_user_octets_from_client{user="hello"} 10598495163 (9.87 GB)
telemt_user_octets_to_client{user="hello"} 236172783974 (219.95 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 88
```