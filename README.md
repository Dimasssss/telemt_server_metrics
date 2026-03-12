# Server Metrics 2026-03-12 18:09:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 43840.7 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1576803
telemt_connections_bad_total 20489
telemt_handshake_timeouts_total 14774
telemt_upstream_connect_attempt_total 8735
telemt_upstream_connect_success_total 8684
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 8735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 533
telemt_me_reconnect_attempts_total 15298
telemt_me_reconnect_success_total 6453
telemt_me_reader_eof_total 6982
telemt_me_idle_close_by_peer_total 6981
telemt_me_route_drop_no_conn_total 615342
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1476861
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7541
telemt_desync_full_logged_total 1916
telemt_desync_suppressed_total 5625
telemt_desync_frames_bucket_total{bucket="1_2"} 1953
telemt_desync_frames_bucket_total{bucket="3_10"} 2744
telemt_desync_frames_bucket_total{bucket="gt_10"} 2844
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6819
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6440
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 366
telemt_user_connections_total{user="hello"} 1476351
telemt_user_connections_current{user="hello"} 1589
telemt_user_octets_from_client{user="hello"} 22445295676 (20.90 GB)
telemt_user_octets_to_client{user="hello"} 486284826876 (452.89 GB)
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 73461.2 (20h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 681254
telemt_connections_bad_total 8923
telemt_handshake_timeouts_total 29264
telemt_upstream_connect_attempt_total 18884
telemt_upstream_connect_success_total 18855
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 18884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8772
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3343
telemt_me_reconnect_attempts_total 13604
telemt_me_reconnect_success_total 13519
telemt_me_reader_eof_total 14363
telemt_me_idle_close_by_peer_total 14363
telemt_me_route_drop_no_conn_total 216793
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 612483
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2654
telemt_desync_full_logged_total 812
telemt_desync_suppressed_total 1842
telemt_desync_frames_bucket_total{bucket="1_2"} 1085
telemt_desync_frames_bucket_total{bucket="3_10"} 867
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 13660
telemt_me_writer_restored_same_endpoint_total 13510
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 614363
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 9330564672 (8.69 GB)
telemt_user_octets_to_client{user="hello"} 231270918647 (215.39 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 73461.0 (20h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1415281
telemt_connections_bad_total 6898
telemt_handshake_timeouts_total 99089
telemt_upstream_connect_attempt_total 17449
telemt_upstream_connect_success_total 17444
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1141
telemt_me_reconnect_attempts_total 14640
telemt_me_reconnect_success_total 13398
telemt_me_reader_eof_total 14124
telemt_me_idle_close_by_peer_total 14123
telemt_me_route_drop_no_conn_total 463054
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1077567
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4545
telemt_desync_full_logged_total 1408
telemt_desync_suppressed_total 3137
telemt_desync_frames_bucket_total{bucket="1_2"} 703
telemt_desync_frames_bucket_total{bucket="3_10"} 1653
telemt_desync_frames_bucket_total{bucket="gt_10"} 2189
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 13511
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 13357
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 1077432
telemt_user_connections_current{user="hello"} 973
telemt_user_octets_from_client{user="hello"} 16195171088 (15.08 GB)
telemt_user_octets_to_client{user="hello"} 388103902941 (361.45 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 73461.7 (20h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 857353
telemt_connections_bad_total 11089
telemt_handshake_timeouts_total 64536
telemt_upstream_connect_attempt_total 19132
telemt_upstream_connect_success_total 19057
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 19132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1613
telemt_me_reconnect_attempts_total 23095
telemt_me_reconnect_success_total 15375
telemt_me_reader_eof_total 16417
telemt_me_idle_close_by_peer_total 16417
telemt_me_route_drop_no_conn_total 300432
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 742741
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1704
telemt_desync_full_logged_total 568
telemt_desync_suppressed_total 1136
telemt_desync_frames_bucket_total{bucket="1_2"} 477
telemt_desync_frames_bucket_total{bucket="3_10"} 660
telemt_desync_frames_bucket_total{bucket="gt_10"} 567
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 15738
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 15354
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 363
telemt_user_connections_total{user="hello"} 742155
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 9083607044 (8.46 GB)
telemt_user_octets_to_client{user="hello"} 299212019712 (278.66 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 73461.3 (20h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 963930
telemt_connections_bad_total 11403
telemt_handshake_timeouts_total 7875
telemt_upstream_connect_attempt_total 23310
telemt_upstream_connect_success_total 23034
telemt_upstream_connect_fail_total 276
telemt_upstream_connect_attempts_per_request{bucket="1"} 23310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11118
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 276
telemt_me_keepalive_timeout_total 1325
telemt_me_reconnect_attempts_total 30365
telemt_me_reconnect_success_total 19333
telemt_me_reader_eof_total 20317
telemt_me_idle_close_by_peer_total 20317
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 357241
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 885301
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3431
telemt_desync_full_logged_total 1186
telemt_desync_suppressed_total 2245
telemt_desync_frames_bucket_total{bucket="1_2"} 957
telemt_desync_frames_bucket_total{bucket="3_10"} 1160
telemt_desync_frames_bucket_total{bucket="gt_10"} 1314
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 19894
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19289
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 885181
telemt_user_connections_current{user="hello"} 824
telemt_user_octets_from_client{user="hello"} 10887872948 (10.14 GB)
telemt_user_octets_to_client{user="hello"} 283181729912 (263.73 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 101
```