# Server Metrics 2026-03-15 14:56:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 60090.1 (16h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1893113
telemt_connections_bad_total 102309
telemt_handshake_timeouts_total 21521
telemt_upstream_connect_attempt_total 11954
telemt_upstream_connect_success_total 11903
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 11954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13785
telemt_me_reconnect_success_total 8894
telemt_me_reader_eof_total 9516
telemt_me_idle_close_by_peer_total 9516
telemt_me_route_drop_no_conn_total 648588
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1602486
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6129
telemt_desync_full_logged_total 1698
telemt_desync_suppressed_total 4431
telemt_desync_frames_bucket_total{bucket="1_2"} 1518
telemt_desync_frames_bucket_total{bucket="3_10"} 2362
telemt_desync_frames_bucket_total{bucket="gt_10"} 2249
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9192
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8883
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 1602077
telemt_user_connections_current{user="hello"} 2475
telemt_user_octets_from_client{user="hello"} 22786159772 (21.22 GB)
telemt_user_octets_to_client{user="hello"} 625001436544 (582.08 GB)
telemt_user_unique_ips_current{user="hello"} 692
telemt_user_unique_ips_recent_window{user="hello"} 344
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 60091.3 (16h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 762350
telemt_connections_bad_total 41068
telemt_handshake_timeouts_total 58369
telemt_upstream_connect_attempt_total 15183
telemt_upstream_connect_success_total 15110
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 15183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6897
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 11854
telemt_me_reconnect_success_total 11759
telemt_me_reader_eof_total 12427
telemt_me_idle_close_by_peer_total 12427
telemt_me_route_drop_no_conn_total 190247
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 576304
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1994
telemt_desync_full_logged_total 690
telemt_desync_suppressed_total 1304
telemt_desync_frames_bucket_total{bucket="1_2"} 739
telemt_desync_frames_bucket_total{bucket="3_10"} 731
telemt_desync_frames_bucket_total{bucket="gt_10"} 524
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 11908
telemt_me_writer_restored_same_endpoint_total 11747
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 576551
telemt_user_connections_current{user="hello"} 626
telemt_user_octets_from_client{user="hello"} 8014503187 (7.46 GB)
telemt_user_octets_to_client{user="hello"} 216766780648 (201.88 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 60091.0 (16h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1664541
telemt_connections_bad_total 47181
telemt_handshake_timeouts_total 168043
telemt_upstream_connect_attempt_total 13235
telemt_upstream_connect_success_total 13173
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 13235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11395
telemt_me_reconnect_success_total 10137
telemt_me_reader_eof_total 10734
telemt_me_idle_close_by_peer_total 10734
telemt_me_route_drop_no_conn_total 446540
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1019659
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2533
telemt_desync_full_logged_total 936
telemt_desync_suppressed_total 1597
telemt_desync_frames_bucket_total{bucket="1_2"} 584
telemt_desync_frames_bucket_total{bucket="3_10"} 981
telemt_desync_frames_bucket_total{bucket="gt_10"} 968
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10313
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10118
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 1015666
telemt_user_connections_current{user="hello"} 1403
telemt_user_octets_from_client{user="hello"} 14775467848 (13.76 GB)
telemt_user_octets_to_client{user="hello"} 365647464664 (340.54 GB)
telemt_user_unique_ips_current{user="hello"} 397
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 60090.9 (16h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 800967
telemt_connections_bad_total 73855
telemt_handshake_timeouts_total 41264
telemt_upstream_connect_attempt_total 167458
telemt_upstream_connect_success_total 166961
telemt_upstream_connect_fail_total 497
telemt_upstream_connect_attempts_per_request{bucket="1"} 167458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12227
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 497
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 52321
telemt_me_reconnect_success_total 11884
telemt_me_reader_eof_total 13482
telemt_me_idle_close_by_peer_total 13482
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 174336
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 460829
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1224
telemt_desync_full_logged_total 316
telemt_desync_suppressed_total 908
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 501
telemt_desync_frames_bucket_total{bucket="gt_10"} 390
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13264
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 11852
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1380
telemt_user_connections_total{user="hello"} 612761
telemt_user_connections_current{user="hello"} 904
telemt_user_octets_from_client{user="hello"} 11753093866 (10.95 GB)
telemt_user_octets_to_client{user="hello"} 205468119865 (191.36 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 60091.8 (16h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 812382
telemt_connections_bad_total 9425
telemt_handshake_timeouts_total 17247
telemt_upstream_connect_attempt_total 13228
telemt_upstream_connect_success_total 13157
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 13228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 13827
telemt_me_reconnect_success_total 10147
telemt_me_reader_eof_total 10848
telemt_me_idle_close_by_peer_total 10848
telemt_me_route_drop_no_conn_total 201795
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 664394
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2338
telemt_desync_full_logged_total 791
telemt_desync_suppressed_total 1547
telemt_desync_frames_bucket_total{bucket="1_2"} 709
telemt_desync_frames_bucket_total{bucket="3_10"} 898
telemt_desync_frames_bucket_total{bucket="gt_10"} 731
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10380
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 10139
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 664439
telemt_user_connections_current{user="hello"} 866
telemt_user_octets_from_client{user="hello"} 8325105904 (7.75 GB)
telemt_user_octets_to_client{user="hello"} 245368994244 (228.52 GB)
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 112
```