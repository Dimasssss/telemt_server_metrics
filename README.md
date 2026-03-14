# Server Metrics 2026-03-14 10:45:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 190028.1 (52h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5461573
telemt_connections_bad_total 56090
telemt_handshake_timeouts_total 120369
telemt_upstream_connect_attempt_total 39965
telemt_upstream_connect_success_total 39709
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 39965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 7621
telemt_me_reconnect_attempts_total 41904
telemt_me_reconnect_success_total 27902
telemt_me_reader_eof_total 29980
telemt_me_idle_close_by_peer_total 29979
telemt_me_route_drop_no_conn_total 2065076
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5006805
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19098
telemt_desync_full_logged_total 5239
telemt_desync_suppressed_total 13859
telemt_desync_frames_bucket_total{bucket="1_2"} 4671
telemt_desync_frames_bucket_total{bucket="3_10"} 7278
telemt_desync_frames_bucket_total{bucket="gt_10"} 7149
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 28745
telemt_me_refill_failed_total 432
telemt_me_writer_restored_same_endpoint_total 27889
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 843
telemt_user_connections_total{user="hello"} 5008266
telemt_user_connections_current{user="hello"} 1805
telemt_user_octets_from_client{user="hello"} 76884687996 (71.60 GB)
telemt_user_octets_to_client{user="hello"} 1593898765889 (1.45 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 488
telemt_user_unique_ips_recent_window{user="hello"} 258
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 89692.0 (24h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1015982
telemt_connections_bad_total 58347
telemt_handshake_timeouts_total 22343
telemt_upstream_connect_attempt_total 23616
telemt_upstream_connect_success_total 23322
telemt_upstream_connect_fail_total 294
telemt_upstream_connect_attempts_per_request{bucket="1"} 23616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10340
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 45
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 255
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 294
telemt_me_keepalive_timeout_total 2285
telemt_me_reconnect_attempts_total 26707
telemt_me_reconnect_success_total 16829
telemt_me_reader_eof_total 18022
telemt_me_idle_close_by_peer_total 18021
telemt_me_route_drop_no_conn_total 341734
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 830431
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2344
telemt_desync_full_logged_total 731
telemt_desync_suppressed_total 1613
telemt_desync_frames_bucket_total{bucket="1_2"} 569
telemt_desync_frames_bucket_total{bucket="3_10"} 991
telemt_desync_frames_bucket_total{bucket="gt_10"} 784
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 17376
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 16821
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 547
telemt_user_connections_total{user="hello"} 832333
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 9039055909 (8.42 GB)
telemt_user_octets_to_client{user="hello"} 291304325036 (271.30 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 219648.5 (61h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3879751
telemt_connections_bad_total 45772
telemt_handshake_timeouts_total 257159
telemt_upstream_connect_attempt_total 49584
telemt_upstream_connect_success_total 49563
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 49584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11031
telemt_me_reconnect_attempts_total 44308
telemt_me_reconnect_success_total 38314
telemt_me_reader_eof_total 40691
telemt_me_idle_close_by_peer_total 40690
telemt_me_route_drop_no_conn_total 1332347
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3243719
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10398
telemt_desync_full_logged_total 3532
telemt_desync_suppressed_total 6866
telemt_desync_frames_bucket_total{bucket="1_2"} 1883
telemt_desync_frames_bucket_total{bucket="3_10"} 3762
telemt_desync_frames_bucket_total{bucket="gt_10"} 4753
telemt_pool_swap_total 203
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 38882
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 38273
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 3242858
telemt_user_connections_current{user="hello"} 929
telemt_user_octets_from_client{user="hello"} 54830301048 (51.06 GB)
telemt_user_octets_to_client{user="hello"} 1163187049017 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 219651.3 (61h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2554838
telemt_connections_bad_total 23428
telemt_handshake_timeouts_total 323988
telemt_upstream_connect_attempt_total 67966
telemt_upstream_connect_success_total 65461
telemt_upstream_connect_fail_total 2368
telemt_upstream_connect_attempts_per_request{bucket="1"} 67692
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39046
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26249
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2367
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20761
telemt_me_reconnect_attempts_total 59168
telemt_me_reconnect_success_total 47510
telemt_me_reader_eof_total 50896
telemt_me_idle_close_by_peer_total 50888
telemt_me_route_drop_no_conn_total 851108
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2000347
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4054
telemt_desync_full_logged_total 1328
telemt_desync_suppressed_total 2726
telemt_desync_frames_bucket_total{bucket="1_2"} 1145
telemt_desync_frames_bucket_total{bucket="3_10"} 1656
telemt_desync_frames_bucket_total{bucket="gt_10"} 1253
telemt_pool_swap_total 189
telemt_me_writer_removed_unexpected_total 48286
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 47486
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 776
telemt_user_connections_total{user="hello"} 2006583
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 29827810507 (27.78 GB)
telemt_user_octets_to_client{user="hello"} 721384159414 (671.84 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 89084.8 (24h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1002486
telemt_connections_bad_total 17231
telemt_handshake_timeouts_total 13135
telemt_upstream_connect_attempt_total 22208
telemt_upstream_connect_success_total 21614
telemt_upstream_connect_fail_total 594
telemt_upstream_connect_attempts_per_request{bucket="1"} 22208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 594
telemt_me_keepalive_timeout_total 1710
telemt_me_reconnect_attempts_total 75377
telemt_me_reconnect_success_total 17188
telemt_me_reader_eof_total 19416
telemt_me_idle_close_by_peer_total 19415
telemt_me_route_drop_no_conn_total 388144
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 927759
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2523
telemt_desync_full_logged_total 785
telemt_desync_suppressed_total 1738
telemt_desync_frames_bucket_total{bucket="1_2"} 859
telemt_desync_frames_bucket_total{bucket="3_10"} 928
telemt_desync_frames_bucket_total{bucket="gt_10"} 736
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19164
telemt_me_refill_failed_total 1813
telemt_me_writer_restored_same_endpoint_total 17183
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1976
telemt_user_connections_total{user="hello"} 927697
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 16552031956 (15.42 GB)
telemt_user_octets_to_client{user="hello"} 310622508792 (289.29 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 103
```