# Server Metrics 2026-03-15 14:15:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 57637.3 (16h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1769707
telemt_connections_bad_total 97365
telemt_handshake_timeouts_total 19340
telemt_upstream_connect_attempt_total 11431
telemt_upstream_connect_success_total 11382
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13389
telemt_me_reconnect_success_total 8500
telemt_me_reader_eof_total 9102
telemt_me_idle_close_by_peer_total 9102
telemt_me_route_drop_no_conn_total 605527
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1495548
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5612
telemt_desync_full_logged_total 1566
telemt_desync_suppressed_total 4046
telemt_desync_frames_bucket_total{bucket="1_2"} 1430
telemt_desync_frames_bucket_total{bucket="3_10"} 2175
telemt_desync_frames_bucket_total{bucket="gt_10"} 2007
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8788
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8489
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 1495171
telemt_user_connections_current{user="hello"} 2129
telemt_user_octets_from_client{user="hello"} 21294633024 (19.83 GB)
telemt_user_octets_to_client{user="hello"} 590531322204 (549.98 GB)
telemt_user_unique_ips_current{user="hello"} 627
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 57638.1 (16h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 718976
telemt_connections_bad_total 39128
telemt_handshake_timeouts_total 57354
telemt_upstream_connect_attempt_total 14708
telemt_upstream_connect_success_total 14637
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 14708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6664
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 11503
telemt_me_reconnect_success_total 11412
telemt_me_reader_eof_total 12063
telemt_me_idle_close_by_peer_total 12063
telemt_me_route_drop_no_conn_total 178747
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 539468
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1981
telemt_desync_full_logged_total 683
telemt_desync_suppressed_total 1298
telemt_desync_frames_bucket_total{bucket="1_2"} 738
telemt_desync_frames_bucket_total{bucket="3_10"} 722
telemt_desync_frames_bucket_total{bucket="gt_10"} 521
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11553
telemt_me_writer_restored_same_endpoint_total 11400
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 539722
telemt_user_connections_current{user="hello"} 787
telemt_user_octets_from_client{user="hello"} 7596858235 (7.08 GB)
telemt_user_octets_to_client{user="hello"} 203006321668 (189.06 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 57637.9 (16h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1534797
telemt_connections_bad_total 45243
telemt_handshake_timeouts_total 158947
telemt_upstream_connect_attempt_total 12686
telemt_upstream_connect_success_total 12628
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 12686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 10981
telemt_me_reconnect_success_total 9727
telemt_me_reader_eof_total 10309
telemt_me_idle_close_by_peer_total 10309
telemt_me_route_drop_no_conn_total 422410
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 952585
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2409
telemt_desync_full_logged_total 890
telemt_desync_suppressed_total 1519
telemt_desync_frames_bucket_total{bucket="1_2"} 553
telemt_desync_frames_bucket_total{bucket="3_10"} 921
telemt_desync_frames_bucket_total{bucket="gt_10"} 935
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9896
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9708
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 948682
telemt_user_connections_current{user="hello"} 1288
telemt_user_octets_from_client{user="hello"} 13773945144 (12.83 GB)
telemt_user_octets_to_client{user="hello"} 343492655560 (319.90 GB)
telemt_user_unique_ips_current{user="hello"} 393
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 57637.9 (16h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 736541
telemt_connections_bad_total 71494
telemt_handshake_timeouts_total 39507
telemt_upstream_connect_attempt_total 127435
telemt_upstream_connect_success_total 126970
telemt_upstream_connect_fail_total 463
telemt_upstream_connect_attempts_per_request{bucket="1"} 127433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 115974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10985
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 463
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 49507
telemt_me_reconnect_success_total 11794
telemt_me_reader_eof_total 13304
telemt_me_idle_close_by_peer_total 13304
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 170381
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 445834
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1172
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 875
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 475
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 13083
telemt_me_refill_failed_total 1179
telemt_me_writer_restored_same_endpoint_total 11762
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1289
telemt_user_connections_total{user="hello"} 558003
telemt_user_connections_current{user="hello"} 849
telemt_user_octets_from_client{user="hello"} 10165904453 (9.47 GB)
telemt_user_octets_to_client{user="hello"} 189984722728 (176.94 GB)
telemt_user_msgs_from_client{user="hello"} 2158176
telemt_user_msgs_to_client{user="hello"} 8185241
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 57638.9 (16h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 760496
telemt_connections_bad_total 9269
telemt_handshake_timeouts_total 15924
telemt_upstream_connect_attempt_total 12687
telemt_upstream_connect_success_total 12619
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 12687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 13411
telemt_me_reconnect_success_total 9737
telemt_me_reader_eof_total 10411
telemt_me_idle_close_by_peer_total 10411
telemt_me_route_drop_no_conn_total 188428
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 617331
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2271
telemt_desync_full_logged_total 759
telemt_desync_suppressed_total 1512
telemt_desync_frames_bucket_total{bucket="1_2"} 679
telemt_desync_frames_bucket_total{bucket="3_10"} 885
telemt_desync_frames_bucket_total{bucket="gt_10"} 707
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9966
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9729
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 617370
telemt_user_connections_current{user="hello"} 938
telemt_user_octets_from_client{user="hello"} 7736253148 (7.20 GB)
telemt_user_octets_to_client{user="hello"} 231652477600 (215.74 GB)
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 116
```