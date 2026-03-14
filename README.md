# Server Metrics 2026-03-14 07:21:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 177744.7 (49h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5012317
telemt_connections_bad_total 40284
telemt_handshake_timeouts_total 114186
telemt_upstream_connect_attempt_total 37273
telemt_upstream_connect_success_total 37030
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 37273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16772
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_keepalive_timeout_total 7343
telemt_me_reconnect_attempts_total 36007
telemt_me_reconnect_success_total 25856
telemt_me_reader_eof_total 27738
telemt_me_idle_close_by_peer_total 27737
telemt_me_route_drop_no_conn_total 1897114
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4598076
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17509
telemt_desync_full_logged_total 4763
telemt_desync_suppressed_total 12746
telemt_desync_frames_bucket_total{bucket="1_2"} 4372
telemt_desync_frames_bucket_total{bucket="3_10"} 6660
telemt_desync_frames_bucket_total{bucket="gt_10"} 6477
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 26542
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25843
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 686
telemt_user_connections_total{user="hello"} 4599565
telemt_user_connections_current{user="hello"} 1444
telemt_user_octets_from_client{user="hello"} 67907443072 (63.24 GB)
telemt_user_octets_to_client{user="hello"} 1456895555637 (1.33 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 415
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 77408.1 (21h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 844299
telemt_connections_bad_total 53892
telemt_handshake_timeouts_total 15385
telemt_upstream_connect_attempt_total 20841
telemt_upstream_connect_success_total 20569
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 20841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9029
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 2145
telemt_me_reconnect_attempts_total 18172
telemt_me_reconnect_success_total 14706
telemt_me_reader_eof_total 15629
telemt_me_idle_close_by_peer_total 15628
telemt_me_route_drop_no_conn_total 277412
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 675130
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1973
telemt_desync_full_logged_total 606
telemt_desync_suppressed_total 1367
telemt_desync_frames_bucket_total{bucket="1_2"} 415
telemt_desync_frames_bucket_total{bucket="3_10"} 876
telemt_desync_frames_bucket_total{bucket="gt_10"} 682
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 15023
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14698
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 317
telemt_user_connections_total{user="hello"} 677044
telemt_user_connections_current{user="hello"} 550
telemt_user_octets_from_client{user="hello"} 7079248029 (6.59 GB)
telemt_user_octets_to_client{user="hello"} 232152363808 (216.21 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 207364.7 (57h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3593975
telemt_connections_bad_total 42314
telemt_handshake_timeouts_total 235946
telemt_upstream_connect_attempt_total 46809
telemt_upstream_connect_success_total 46788
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 46809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21878
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10707
telemt_me_reconnect_attempts_total 41136
telemt_me_reconnect_success_total 36159
telemt_me_reader_eof_total 38411
telemt_me_idle_close_by_peer_total 38410
telemt_me_route_drop_no_conn_total 1229216
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2997280
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9867
telemt_desync_full_logged_total 3316
telemt_desync_suppressed_total 6551
telemt_desync_frames_bucket_total{bucket="1_2"} 1725
telemt_desync_frames_bucket_total{bucket="3_10"} 3566
telemt_desync_frames_bucket_total{bucket="gt_10"} 4576
telemt_pool_swap_total 197
telemt_me_writer_removed_unexpected_total 36660
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36118
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 501
telemt_user_connections_total{user="hello"} 2996433
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 50127120400 (46.68 GB)
telemt_user_octets_to_client{user="hello"} 1070814360385 (997.27 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 207367.4 (57h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2392745
telemt_connections_bad_total 23305
telemt_handshake_timeouts_total 286511
telemt_upstream_connect_attempt_total 64643
telemt_upstream_connect_success_total 62152
telemt_upstream_connect_fail_total 2354
telemt_upstream_connect_attempts_per_request{bucket="1"} 64369
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24900
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2353
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20522
telemt_me_reconnect_attempts_total 53889
telemt_me_reconnect_success_total 44810
telemt_me_reader_eof_total 48009
telemt_me_idle_close_by_peer_total 48002
telemt_me_route_drop_no_conn_total 805089
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1885030
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3927
telemt_desync_full_logged_total 1277
telemt_desync_suppressed_total 2650
telemt_desync_frames_bucket_total{bucket="1_2"} 1078
telemt_desync_frames_bucket_total{bucket="3_10"} 1618
telemt_desync_frames_bucket_total{bucket="gt_10"} 1231
telemt_pool_swap_total 183
telemt_me_writer_removed_unexpected_total 45478
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 44786
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 668
telemt_user_connections_total{user="hello"} 1891118
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 28433846427 (26.48 GB)
telemt_user_octets_to_client{user="hello"} 693660394046 (646.02 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 76801.0 (21h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 815645
telemt_connections_bad_total 8330
telemt_handshake_timeouts_total 9592
telemt_upstream_connect_attempt_total 19659
telemt_upstream_connect_success_total 19130
telemt_upstream_connect_fail_total 529
telemt_upstream_connect_attempts_per_request{bucket="1"} 19659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9948
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 529
telemt_me_keepalive_timeout_total 1587
telemt_me_reconnect_attempts_total 61910
telemt_me_reconnect_success_total 15290
telemt_me_reader_eof_total 17113
telemt_me_idle_close_by_peer_total 17112
telemt_me_route_drop_no_conn_total 314659
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 762021
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1875
telemt_desync_full_logged_total 595
telemt_desync_suppressed_total 1280
telemt_desync_frames_bucket_total{bucket="1_2"} 562
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 591
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 16875
telemt_me_refill_failed_total 1452
telemt_me_writer_restored_same_endpoint_total 15285
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1585
telemt_user_connections_total{user="hello"} 761881
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 13552221892 (12.62 GB)
telemt_user_octets_to_client{user="hello"} 257009132964 (239.36 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 58
```