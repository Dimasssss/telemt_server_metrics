# Server Metrics 2026-03-12 09:33:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 12915.9 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411779
telemt_connections_bad_total 1337
telemt_handshake_timeouts_total 2508
telemt_upstream_connect_attempt_total 2505
telemt_upstream_connect_success_total 2490
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 272
telemt_me_reconnect_attempts_total 1811
telemt_me_reconnect_success_total 1799
telemt_me_reader_eof_total 1865
telemt_me_idle_close_by_peer_total 1865
telemt_me_route_drop_no_conn_total 140020
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 398469
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1869
telemt_desync_full_logged_total 466
telemt_desync_suppressed_total 1403
telemt_desync_frames_bucket_total{bucket="1_2"} 480
telemt_desync_frames_bucket_total{bucket="3_10"} 681
telemt_desync_frames_bucket_total{bucket="gt_10"} 708
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1815
telemt_me_writer_restored_same_endpoint_total 1786
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 398343
telemt_user_connections_current{user="hello"} 1319
telemt_user_octets_from_client{user="hello"} 5983355512 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 107568522496 (100.18 GB)
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 42536.3 (11h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254505
telemt_connections_bad_total 2974
telemt_handshake_timeouts_total 8051
telemt_upstream_connect_attempt_total 10812
telemt_upstream_connect_success_total 10806
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 10812
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 656
telemt_me_reconnect_attempts_total 8527
telemt_me_reconnect_success_total 8484
telemt_me_reader_eof_total 9020
telemt_me_idle_close_by_peer_total 9020
telemt_me_route_drop_no_conn_total 73037
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 225628
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 476
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 281
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8551
telemt_me_writer_restored_same_endpoint_total 8475
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 226018
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 3259128407 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 87203091678 (81.21 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 42536.2 (11h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 680135
telemt_connections_bad_total 3059
telemt_handshake_timeouts_total 50171
telemt_upstream_connect_attempt_total 10839
telemt_upstream_connect_success_total 10834
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 10839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4759
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 542
telemt_me_reconnect_attempts_total 8411
telemt_me_reconnect_success_total 8339
telemt_me_reader_eof_total 8760
telemt_me_idle_close_by_peer_total 8760
telemt_me_route_drop_no_conn_total 144295
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 415082
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1882
telemt_desync_full_logged_total 571
telemt_desync_suppressed_total 1311
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 642
telemt_desync_frames_bucket_total{bucket="gt_10"} 999
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8341
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8298
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 415346
telemt_user_connections_current{user="hello"} 962
telemt_user_octets_from_client{user="hello"} 5125526396 (4.77 GB)
telemt_user_octets_to_client{user="hello"} 138983514593 (129.44 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 42536.8 (11h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336899
telemt_connections_bad_total 1827
telemt_handshake_timeouts_total 24143
telemt_upstream_connect_attempt_total 11641
telemt_upstream_connect_success_total 11594
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 11641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 810
telemt_me_reconnect_attempts_total 9484
telemt_me_reconnect_success_total 9448
telemt_me_reader_eof_total 10018
telemt_me_idle_close_by_peer_total 10018
telemt_me_route_drop_no_conn_total 114262
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283288
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 580
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 372
telemt_desync_frames_bucket_total{bucket="1_2"} 177
telemt_desync_frames_bucket_total{bucket="3_10"} 239
telemt_desync_frames_bucket_total{bucket="gt_10"} 164
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9508
telemt_me_writer_restored_same_endpoint_total 9427
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 283110
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 3408645824 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 110655739792 (103.06 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 42536.5 (11h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377900
telemt_connections_bad_total 398
telemt_handshake_timeouts_total 2795
telemt_upstream_connect_attempt_total 13804
telemt_upstream_connect_success_total 13637
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 13804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6532
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 596
telemt_me_reconnect_attempts_total 13005
telemt_me_reconnect_success_total 11487
telemt_me_reader_eof_total 11969
telemt_me_idle_close_by_peer_total 11969
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 121343
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 356890
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1508
telemt_desync_full_logged_total 489
telemt_desync_suppressed_total 1019
telemt_desync_frames_bucket_total{bucket="1_2"} 434
telemt_desync_frames_bucket_total{bucket="3_10"} 537
telemt_desync_frames_bucket_total{bucket="gt_10"} 537
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 11638
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 11465
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 356824
telemt_user_connections_current{user="hello"} 792
telemt_user_octets_from_client{user="hello"} 3920607276 (3.65 GB)
telemt_user_octets_to_client{user="hello"} 85829064176 (79.93 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 142
```