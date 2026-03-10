# Server Metrics 2026-03-10 17:07:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 9648.8 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 327706
telemt_connections_bad_total 1360
telemt_handshake_timeouts_total 1593
telemt_upstream_connect_attempt_total 1716
telemt_upstream_connect_success_total 1708
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 916
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 9318
telemt_me_reconnect_success_total 1180
telemt_me_reader_eof_total 1397
telemt_me_idle_close_by_peer_total 1397
telemt_me_route_drop_no_conn_total 144002
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 314694
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1415
telemt_desync_full_logged_total 391
telemt_desync_suppressed_total 1024
telemt_desync_frames_bucket_total{bucket="1_2"} 370
telemt_desync_frames_bucket_total{bucket="3_10"} 524
telemt_desync_frames_bucket_total{bucket="gt_10"} 521
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1427
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 1174
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 314626
telemt_user_connections_current{user="hello"} 1400
telemt_user_octets_from_client{user="hello"} 4075099100 (3.80 GB)
telemt_user_octets_to_client{user="hello"} 92748732252 (86.38 GB)
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 9705.4 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131941
telemt_connections_bad_total 1673
telemt_handshake_timeouts_total 9284
telemt_upstream_connect_attempt_total 2226
telemt_upstream_connect_success_total 2215
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 1708
telemt_me_reconnect_success_total 1697
telemt_me_reader_eof_total 1744
telemt_me_idle_close_by_peer_total 1744
telemt_me_route_drop_no_conn_total 37105
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114196
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 567
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 407
telemt_desync_frames_bucket_total{bucket="1_2"} 221
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1705
telemt_me_writer_restored_same_endpoint_total 1676
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 114176
telemt_user_connections_current{user="hello"} 527
telemt_user_octets_from_client{user="hello"} 1421823712 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 30572812856 (28.47 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 9705.3 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252405
telemt_connections_bad_total 701
telemt_handshake_timeouts_total 28657
telemt_upstream_connect_attempt_total 3288
telemt_upstream_connect_success_total 3232
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 3288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 1704
telemt_me_reconnect_success_total 1664
telemt_me_reader_eof_total 1724
telemt_me_idle_close_by_peer_total 1724
telemt_me_route_drop_no_conn_total 79525
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200854
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 576
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 416
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 192
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1691
telemt_me_writer_restored_same_endpoint_total 1653
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 201830
telemt_user_connections_current{user="hello"} 824
telemt_user_octets_from_client{user="hello"} 2860321637 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 59249066089 (55.18 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 9705.8 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156574
telemt_connections_bad_total 9612
telemt_handshake_timeouts_total 14734
telemt_upstream_connect_attempt_total 2428
telemt_upstream_connect_success_total 2428
telemt_upstream_connect_attempts_per_request{bucket="1"} 2428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1126
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 1920
telemt_me_reconnect_success_total 1910
telemt_me_reader_eof_total 1979
telemt_me_idle_close_by_peer_total 1979
telemt_me_route_drop_no_conn_total 51706
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125280
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 392
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 236
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 137
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1923
telemt_me_writer_restored_same_endpoint_total 1899
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 125126
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 2181406400 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 33727557060 (31.41 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 9705.3 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170130
telemt_connections_bad_total 716
telemt_handshake_timeouts_total 1401
telemt_upstream_connect_attempt_total 3012
telemt_upstream_connect_success_total 3004
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 3012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 2485
telemt_me_reconnect_success_total 2470
telemt_me_reader_eof_total 2527
telemt_me_idle_close_by_peer_total 2527
telemt_me_route_drop_no_conn_total 63541
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159131
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 799
telemt_desync_full_logged_total 280
telemt_desync_suppressed_total 519
telemt_desync_frames_bucket_total{bucket="1_2"} 330
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2490
telemt_me_writer_restored_same_endpoint_total 2470
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 159071
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 2754410096 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 48589332592 (45.25 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 96
```