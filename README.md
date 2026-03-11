# Server Metrics 2026-03-11 03:38:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 47513.8 (13h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 912719
telemt_connections_bad_total 10070
telemt_handshake_timeouts_total 23702
telemt_upstream_connect_attempt_total 10271
telemt_upstream_connect_success_total 10262
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5067
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 524
telemt_me_reconnect_attempts_total 19513
telemt_me_reconnect_success_total 7842
telemt_me_reader_eof_total 8555
telemt_me_idle_close_by_peer_total 8555
telemt_me_route_drop_no_conn_total 354989
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 840830
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3883
telemt_desync_full_logged_total 1077
telemt_desync_suppressed_total 2806
telemt_desync_frames_bucket_total{bucket="1_2"} 1102
telemt_desync_frames_bucket_total{bucket="3_10"} 1461
telemt_desync_frames_bucket_total{bucket="gt_10"} 1320
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 8277
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7836
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 435
telemt_user_connections_total{user="hello"} 840553
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 11205269100 (10.44 GB)
telemt_user_octets_to_client{user="hello"} 250228970084 (233.04 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 47570.6 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 374171
telemt_connections_bad_total 2529
telemt_handshake_timeouts_total 18533
telemt_upstream_connect_attempt_total 18301
telemt_upstream_connect_success_total 15409
telemt_upstream_connect_fail_total 2892
telemt_upstream_connect_attempts_per_request{bucket="1"} 18301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6349
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2892
telemt_me_keepalive_timeout_total 1763
telemt_me_reconnect_attempts_total 10891
telemt_me_reconnect_success_total 10074
telemt_me_reader_eof_total 10640
telemt_me_idle_close_by_peer_total 10638
telemt_me_route_drop_no_conn_total 180981
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320768
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1809
telemt_desync_full_logged_total 530
telemt_desync_suppressed_total 1279
telemt_desync_frames_bucket_total{bucket="1_2"} 555
telemt_desync_frames_bucket_total{bucket="3_10"} 649
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 10193
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 10053
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 323034
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 3078128190 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 75966729080 (70.75 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 47570.3 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 627030
telemt_connections_bad_total 5361
telemt_handshake_timeouts_total 34949
telemt_upstream_connect_attempt_total 12842
telemt_upstream_connect_success_total 12676
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 12842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_keepalive_timeout_total 552
telemt_me_reconnect_attempts_total 20281
telemt_me_reconnect_success_total 9212
telemt_me_reader_eof_total 9993
telemt_me_idle_close_by_peer_total 9993
telemt_me_route_drop_no_conn_total 212664
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 557581
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1613
telemt_desync_full_logged_total 475
telemt_desync_suppressed_total 1138
telemt_desync_frames_bucket_total{bucket="1_2"} 352
telemt_desync_frames_bucket_total{bucket="3_10"} 563
telemt_desync_frames_bucket_total{bucket="gt_10"} 698
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 9682
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 9201
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 470
telemt_user_connections_total{user="hello"} 558475
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 7134164445 (6.64 GB)
telemt_user_octets_to_client{user="hello"} 169676416573 (158.02 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 47570.7 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 473709
telemt_connections_bad_total 44899
telemt_handshake_timeouts_total 47247
telemt_upstream_connect_attempt_total 13867
telemt_upstream_connect_success_total 13867
telemt_upstream_connect_attempts_per_request{bucket="1"} 13867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 474
telemt_me_reconnect_attempts_total 12520
telemt_me_reconnect_success_total 11481
telemt_me_reader_eof_total 12186
telemt_me_idle_close_by_peer_total 12186
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 141038
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 367712
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 785
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 291
telemt_desync_frames_bucket_total{bucket="3_10"} 277
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 11617
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 11462
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 367379
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 4485970152 (4.18 GB)
telemt_user_octets_to_client{user="hello"} 97633148288 (90.93 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 47570.5 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 500314
telemt_connections_bad_total 5811
telemt_handshake_timeouts_total 3117
telemt_upstream_connect_attempt_total 13896
telemt_upstream_connect_success_total 13838
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 13896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6601
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 541
telemt_me_reconnect_attempts_total 15188
telemt_me_reconnect_success_total 11408
telemt_me_reader_eof_total 12037
telemt_me_idle_close_by_peer_total 12037
telemt_me_route_drop_no_conn_total 160211
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 455272
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2357
telemt_desync_full_logged_total 919
telemt_desync_suppressed_total 1438
telemt_desync_frames_bucket_total{bucket="1_2"} 875
telemt_desync_frames_bucket_total{bucket="3_10"} 998
telemt_desync_frames_bucket_total{bucket="gt_10"} 484
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 11670
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 11408
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 454915
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 8629783436 (8.04 GB)
telemt_user_octets_to_client{user="hello"} 162573139232 (151.41 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 47
```