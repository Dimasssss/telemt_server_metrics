# Server Metrics 2026-03-15 13:03:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 53343.6 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1544963
telemt_connections_bad_total 89072
telemt_handshake_timeouts_total 13725
telemt_upstream_connect_attempt_total 10642
telemt_upstream_connect_success_total 10593
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 10642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4966
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 12783
telemt_me_reconnect_success_total 7898
telemt_me_reader_eof_total 8466
telemt_me_idle_close_by_peer_total 8466
telemt_me_route_drop_no_conn_total 520974
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1300786
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4847
telemt_desync_full_logged_total 1372
telemt_desync_suppressed_total 3475
telemt_desync_frames_bucket_total{bucket="1_2"} 1214
telemt_desync_frames_bucket_total{bucket="3_10"} 1898
telemt_desync_frames_bucket_total{bucket="gt_10"} 1735
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8173
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 7887
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 1300430
telemt_user_connections_current{user="hello"} 2458
telemt_user_octets_from_client{user="hello"} 18179964560 (16.93 GB)
telemt_user_octets_to_client{user="hello"} 516818672804 (481.32 GB)
telemt_user_unique_ips_current{user="hello"} 683
telemt_user_unique_ips_recent_window{user="hello"} 352
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 53344.7 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 620185
telemt_connections_bad_total 31794
telemt_handshake_timeouts_total 39567
telemt_upstream_connect_attempt_total 13777
telemt_upstream_connect_success_total 13707
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6181
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 10760
telemt_me_reconnect_success_total 10679
telemt_me_reader_eof_total 11290
telemt_me_idle_close_by_peer_total 11290
telemt_me_route_drop_no_conn_total 156767
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 474709
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1873
telemt_desync_full_logged_total 648
telemt_desync_suppressed_total 1225
telemt_desync_frames_bucket_total{bucket="1_2"} 708
telemt_desync_frames_bucket_total{bucket="3_10"} 682
telemt_desync_frames_bucket_total{bucket="gt_10"} 483
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10802
telemt_me_writer_restored_same_endpoint_total 10667
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 474980
telemt_user_connections_current{user="hello"} 713
telemt_user_octets_from_client{user="hello"} 6648809315 (6.19 GB)
telemt_user_octets_to_client{user="hello"} 177593917628 (165.40 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 53344.5 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1259884
telemt_connections_bad_total 40937
telemt_handshake_timeouts_total 130024
telemt_upstream_connect_attempt_total 11815
telemt_upstream_connect_success_total 11759
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 11815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 10296
telemt_me_reconnect_success_total 9048
telemt_me_reader_eof_total 9588
telemt_me_idle_close_by_peer_total 9588
telemt_me_route_drop_no_conn_total 371676
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 832389
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2162
telemt_desync_full_logged_total 785
telemt_desync_suppressed_total 1377
telemt_desync_frames_bucket_total{bucket="1_2"} 486
telemt_desync_frames_bucket_total{bucket="3_10"} 809
telemt_desync_frames_bucket_total{bucket="gt_10"} 867
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9205
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9029
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 828884
telemt_user_connections_current{user="hello"} 1288
telemt_user_octets_from_client{user="hello"} 12163299336 (11.33 GB)
telemt_user_octets_to_client{user="hello"} 307639043844 (286.51 GB)
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 53344.5 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 624865
telemt_connections_bad_total 67577
telemt_handshake_timeouts_total 34439
telemt_upstream_connect_attempt_total 44066
telemt_upstream_connect_success_total 43652
telemt_upstream_connect_fail_total 413
telemt_upstream_connect_attempts_per_request{bucket="1"} 44065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8492
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 413
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 43961
telemt_me_reconnect_success_total 11754
telemt_me_reader_eof_total 13093
telemt_me_idle_close_by_peer_total 13093
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 166479
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 435762
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1149
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 859
telemt_desync_frames_bucket_total{bucket="1_2"} 310
telemt_desync_frames_bucket_total{bucket="3_10"} 469
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12871
telemt_me_refill_failed_total 1007
telemt_me_writer_restored_same_endpoint_total 11722
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1117
telemt_user_connections_total{user="hello"} 464836
telemt_user_connections_current{user="hello"} 730
telemt_user_octets_from_client{user="hello"} 8855315727 (8.25 GB)
telemt_user_octets_to_client{user="hello"} 162680174381 (151.51 GB)
telemt_user_msgs_from_client{user="hello"} 499247
telemt_user_msgs_to_client{user="hello"} 1860382
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 53345.5 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 662116
telemt_connections_bad_total 8654
telemt_handshake_timeouts_total 13545
telemt_upstream_connect_attempt_total 11898
telemt_upstream_connect_success_total 11836
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 11898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 12812
telemt_me_reconnect_success_total 9144
telemt_me_reader_eof_total 9795
telemt_me_idle_close_by_peer_total 9795
telemt_me_route_drop_no_conn_total 164713
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 537225
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2041
telemt_desync_full_logged_total 683
telemt_desync_suppressed_total 1358
telemt_desync_frames_bucket_total{bucket="1_2"} 592
telemt_desync_frames_bucket_total{bucket="3_10"} 815
telemt_desync_frames_bucket_total{bucket="gt_10"} 634
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9367
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9136
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 537267
telemt_user_connections_current{user="hello"} 850
telemt_user_octets_from_client{user="hello"} 6900932288 (6.43 GB)
telemt_user_octets_to_client{user="hello"} 199000461632 (185.33 GB)
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 126
```