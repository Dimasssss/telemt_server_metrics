# Server Metrics 2026-03-11 16:33:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 93994.2 (26h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2345349
telemt_connections_bad_total 40962
telemt_handshake_timeouts_total 53926
telemt_upstream_connect_attempt_total 19663
telemt_upstream_connect_success_total 19651
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 19663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9662
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5017
telemt_me_reconnect_attempts_total 32759
telemt_me_reconnect_success_total 14885
telemt_me_reader_eof_total 16146
telemt_me_idle_close_by_peer_total 16146
telemt_me_route_drop_no_conn_total 870050
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2145596
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11155
telemt_desync_full_logged_total 3043
telemt_desync_suppressed_total 8112
telemt_desync_frames_bucket_total{bucket="1_2"} 2760
telemt_desync_frames_bucket_total{bucket="3_10"} 4302
telemt_desync_frames_bucket_total{bucket="gt_10"} 4093
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 15607
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14879
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 722
telemt_user_connections_total{user="hello"} 2144050
telemt_user_connections_current{user="hello"} 1453
telemt_user_octets_from_client{user="hello"} 28915905296 (26.93 GB)
telemt_user_octets_to_client{user="hello"} 605185597692 (563.62 GB)
telemt_user_unique_ips_current{user="hello"} 388
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 94050.7 (26h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 877352
telemt_connections_bad_total 15252
telemt_handshake_timeouts_total 69865
telemt_upstream_connect_attempt_total 29632
telemt_upstream_connect_success_total 26672
telemt_upstream_connect_fail_total 2960
telemt_upstream_connect_attempts_per_request{bucket="1"} 29632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11961
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2960
telemt_me_keepalive_timeout_total 2652
telemt_me_reconnect_attempts_total 21091
telemt_me_reconnect_success_total 18993
telemt_me_reader_eof_total 20100
telemt_me_idle_close_by_peer_total 20097
telemt_me_route_drop_no_conn_total 337785
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 737048
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2965
telemt_desync_full_logged_total 947
telemt_desync_suppressed_total 2018
telemt_desync_frames_bucket_total{bucket="1_2"} 909
telemt_desync_frames_bucket_total{bucket="3_10"} 1064
telemt_desync_frames_bucket_total{bucket="gt_10"} 992
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 19263
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 18970
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 739508
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 8423594070 (7.85 GB)
telemt_user_octets_to_client{user="hello"} 209145356588 (194.78 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 94050.6 (26h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1502358
telemt_connections_bad_total 8918
telemt_handshake_timeouts_total 125651
telemt_upstream_connect_attempt_total 24306
telemt_upstream_connect_success_total 23998
telemt_upstream_connect_fail_total 308
telemt_upstream_connect_attempts_per_request{bucket="1"} 24306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 308
telemt_me_keepalive_timeout_total 1725
telemt_me_reconnect_attempts_total 41928
telemt_me_reconnect_success_total 18174
telemt_me_reader_eof_total 19728
telemt_me_idle_close_by_peer_total 19728
telemt_me_route_drop_no_conn_total 549525
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1313109
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3450
telemt_desync_full_logged_total 1020
telemt_desync_suppressed_total 2430
telemt_desync_frames_bucket_total{bucket="1_2"} 860
telemt_desync_frames_bucket_total{bucket="3_10"} 1301
telemt_desync_frames_bucket_total{bucket="gt_10"} 1289
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 19163
telemt_me_refill_failed_total 737
telemt_me_writer_restored_same_endpoint_total 18162
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 989
telemt_user_connections_total{user="hello"} 1312814
telemt_user_connections_current{user="hello"} 826
telemt_user_octets_from_client{user="hello"} 15910818133 (14.82 GB)
telemt_user_octets_to_client{user="hello"} 397801144313 (370.48 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 94050.9 (26h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1083451
telemt_connections_bad_total 77983
telemt_handshake_timeouts_total 104567
telemt_upstream_connect_attempt_total 25316
telemt_upstream_connect_success_total 25316
telemt_upstream_connect_attempts_per_request{bucket="1"} 25316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1119
telemt_me_reconnect_attempts_total 21694
telemt_me_reconnect_success_total 20616
telemt_me_reader_eof_total 21841
telemt_me_idle_close_by_peer_total 21840
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 355430
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 867990
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1793
telemt_desync_full_logged_total 696
telemt_desync_suppressed_total 1097
telemt_desync_frames_bucket_total{bucket="1_2"} 652
telemt_desync_frames_bucket_total{bucket="3_10"} 626
telemt_desync_frames_bucket_total{bucket="gt_10"} 515
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 20870
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 20585
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 867306
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 10413368880 (9.70 GB)
telemt_user_octets_to_client{user="hello"} 256356833492 (238.75 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 94050.7 (26h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1194187
telemt_connections_bad_total 6957
telemt_handshake_timeouts_total 11835
telemt_upstream_connect_attempt_total 25654
telemt_upstream_connect_success_total 25540
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 25654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12283
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 201
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 2122
telemt_me_reconnect_attempts_total 24790
telemt_me_reconnect_success_total 20694
telemt_me_reader_eof_total 21804
telemt_me_idle_close_by_peer_total 21804
telemt_me_route_drop_no_conn_total 426192
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1087699
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4256
telemt_desync_full_logged_total 1518
telemt_desync_suppressed_total 2738
telemt_desync_frames_bucket_total{bucket="1_2"} 1408
telemt_desync_frames_bucket_total{bucket="3_10"} 1587
telemt_desync_frames_bucket_total{bucket="gt_10"} 1261
telemt_pool_swap_total 61
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 21090
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 20694
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 396
telemt_user_connections_total{user="hello"} 1087399
telemt_user_connections_current{user="hello"} 761
telemt_user_octets_from_client{user="hello"} 20391853923 (18.99 GB)
telemt_user_octets_to_client{user="hello"} 376643049306 (350.78 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 115
```