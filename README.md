# Server Metrics 2026-03-11 02:53:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 44771.0 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 866921
telemt_connections_bad_total 10063
telemt_handshake_timeouts_total 16967
telemt_upstream_connect_attempt_total 9722
telemt_upstream_connect_success_total 9713
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 9722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4799
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 510
telemt_me_reconnect_attempts_total 19093
telemt_me_reconnect_success_total 7423
telemt_me_reader_eof_total 8106
telemt_me_idle_close_by_peer_total 8106
telemt_me_route_drop_no_conn_total 345058
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 810944
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3766
telemt_desync_full_logged_total 1045
telemt_desync_suppressed_total 2721
telemt_desync_frames_bucket_total{bucket="1_2"} 1091
telemt_desync_frames_bucket_total{bucket="3_10"} 1418
telemt_desync_frames_bucket_total{bucket="gt_10"} 1257
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 7851
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7417
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 428
telemt_user_connections_total{user="hello"} 810678
telemt_user_connections_current{user="hello"} 544
telemt_user_octets_from_client{user="hello"} 10972742640 (10.22 GB)
telemt_user_octets_to_client{user="hello"} 241289932852 (224.72 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 44827.8 (12h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363900
telemt_connections_bad_total 2414
telemt_handshake_timeouts_total 18296
telemt_upstream_connect_attempt_total 17532
telemt_upstream_connect_success_total 14642
telemt_upstream_connect_fail_total 2890
telemt_upstream_connect_attempts_per_request{bucket="1"} 17532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5941
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2890
telemt_me_keepalive_timeout_total 1751
telemt_me_reconnect_attempts_total 10254
telemt_me_reconnect_success_total 9437
telemt_me_reader_eof_total 9949
telemt_me_idle_close_by_peer_total 9947
telemt_me_route_drop_no_conn_total 178103
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311884
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1793
telemt_desync_full_logged_total 516
telemt_desync_suppressed_total 1277
telemt_desync_frames_bucket_total{bucket="1_2"} 550
telemt_desync_frames_bucket_total{bucket="3_10"} 638
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 9554
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 9416
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 314154
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 2960871742 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 73291367716 (68.26 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 44827.5 (12h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 608231
telemt_connections_bad_total 4922
telemt_handshake_timeouts_total 34695
telemt_upstream_connect_attempt_total 12205
telemt_upstream_connect_success_total 12042
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 12205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 539
telemt_me_reconnect_attempts_total 19777
telemt_me_reconnect_success_total 8709
telemt_me_reader_eof_total 9456
telemt_me_idle_close_by_peer_total 9456
telemt_me_route_drop_no_conn_total 206772
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 539788
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1562
telemt_desync_full_logged_total 460
telemt_desync_suppressed_total 1102
telemt_desync_frames_bucket_total{bucket="1_2"} 347
telemt_desync_frames_bucket_total{bucket="3_10"} 544
telemt_desync_frames_bucket_total{bucket="gt_10"} 671
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 9172
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 8698
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 540687
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 7036449989 (6.55 GB)
telemt_user_octets_to_client{user="hello"} 166013031641 (154.61 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 44828.0 (12h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 457282
telemt_connections_bad_total 42382
telemt_handshake_timeouts_total 44464
telemt_upstream_connect_attempt_total 13033
telemt_upstream_connect_success_total 13033
telemt_upstream_connect_attempts_per_request{bucket="1"} 13033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5695
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 459
telemt_me_reconnect_attempts_total 11815
telemt_me_reconnect_success_total 10777
telemt_me_reader_eof_total 11431
telemt_me_idle_close_by_peer_total 11431
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 136778
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 356775
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 768
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 462
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 10906
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 10758
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 356444
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 4359867152 (4.06 GB)
telemt_user_octets_to_client{user="hello"} 95277844564 (88.73 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 44827.6 (12h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 482153
telemt_connections_bad_total 5793
telemt_handshake_timeouts_total 3037
telemt_upstream_connect_attempt_total 13178
telemt_upstream_connect_success_total 13123
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 13178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6231
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 531
telemt_me_reconnect_attempts_total 14604
telemt_me_reconnect_success_total 10827
telemt_me_reader_eof_total 11417
telemt_me_idle_close_by_peer_total 11417
telemt_me_route_drop_no_conn_total 155672
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 439522
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2317
telemt_desync_full_logged_total 904
telemt_desync_suppressed_total 1413
telemt_desync_frames_bucket_total{bucket="1_2"} 859
telemt_desync_frames_bucket_total{bucket="3_10"} 984
telemt_desync_frames_bucket_total{bucket="gt_10"} 474
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 11086
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 10827
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 439186
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 8548382072 (7.96 GB)
telemt_user_octets_to_client{user="hello"} 159293593128 (148.35 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 31
```