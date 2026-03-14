# Server Metrics 2026-03-14 12:02:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 194631.2 (54h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5634851
telemt_connections_bad_total 59020
telemt_handshake_timeouts_total 123929
telemt_upstream_connect_attempt_total 40781
telemt_upstream_connect_success_total 40520
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 40781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_keepalive_timeout_total 7841
telemt_me_reconnect_attempts_total 44861
telemt_me_reconnect_success_total 28488
telemt_me_reader_eof_total 30665
telemt_me_idle_close_by_peer_total 30664
telemt_me_route_drop_no_conn_total 2132878
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5169536
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19959
telemt_desync_full_logged_total 5455
telemt_desync_suppressed_total 14504
telemt_desync_frames_bucket_total{bucket="1_2"} 4835
telemt_desync_frames_bucket_total{bucket="3_10"} 7601
telemt_desync_frames_bucket_total{bucket="gt_10"} 7523
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 29414
telemt_me_refill_failed_total 506
telemt_me_writer_restored_same_endpoint_total 28475
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 926
telemt_user_connections_total{user="hello"} 5171048
telemt_user_connections_current{user="hello"} 1914
telemt_user_octets_from_client{user="hello"} 80252829756 (74.74 GB)
telemt_user_octets_to_client{user="hello"} 1645059852557 (1.50 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 94295.1 (26h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1082870
telemt_connections_bad_total 58928
telemt_handshake_timeouts_total 24817
telemt_upstream_connect_attempt_total 24414
telemt_upstream_connect_success_total 24113
telemt_upstream_connect_fail_total 301
telemt_upstream_connect_attempts_per_request{bucket="1"} 24414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10674
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 301
telemt_me_keepalive_timeout_total 2401
telemt_me_reconnect_attempts_total 33773
telemt_me_reconnect_success_total 17396
telemt_me_reader_eof_total 18799
telemt_me_idle_close_by_peer_total 18798
telemt_me_route_drop_no_conn_total 365650
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 891558
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2463
telemt_desync_full_logged_total 773
telemt_desync_suppressed_total 1690
telemt_desync_frames_bucket_total{bucket="1_2"} 634
telemt_desync_frames_bucket_total{bucket="3_10"} 1024
telemt_desync_frames_bucket_total{bucket="gt_10"} 805
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18154
telemt_me_refill_failed_total 505
telemt_me_writer_restored_same_endpoint_total 17388
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 758
telemt_user_connections_total{user="hello"} 893471
telemt_user_connections_current{user="hello"} 785
telemt_user_octets_from_client{user="hello"} 9778164313 (9.11 GB)
telemt_user_octets_to_client{user="hello"} 315091984812 (293.45 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 224251.7 (62h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3996939
telemt_connections_bad_total 46209
telemt_handshake_timeouts_total 272441
telemt_upstream_connect_attempt_total 50550
telemt_upstream_connect_success_total 50529
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 50550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23597
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11267
telemt_me_reconnect_attempts_total 45024
telemt_me_reconnect_success_total 39023
telemt_me_reader_eof_total 41451
telemt_me_idle_close_by_peer_total 41449
telemt_me_route_drop_no_conn_total 1373050
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3342816
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10751
telemt_desync_full_logged_total 3631
telemt_desync_suppressed_total 7120
telemt_desync_frames_bucket_total{bucket="1_2"} 1956
telemt_desync_frames_bucket_total{bucket="3_10"} 3888
telemt_desync_frames_bucket_total{bucket="gt_10"} 4907
telemt_pool_swap_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 39600
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 38982
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 3341962
telemt_user_connections_current{user="hello"} 1011
telemt_user_octets_from_client{user="hello"} 57212548740 (53.28 GB)
telemt_user_octets_to_client{user="hello"} 1194850963325 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 224254.4 (62h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2614652
telemt_connections_bad_total 23510
telemt_handshake_timeouts_total 336743
telemt_upstream_connect_attempt_total 69213
telemt_upstream_connect_success_total 66705
telemt_upstream_connect_fail_total 2371
telemt_upstream_connect_attempts_per_request{bucket="1"} 68939
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26821
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2370
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20959
telemt_me_reconnect_attempts_total 61275
telemt_me_reconnect_success_total 48494
telemt_me_reader_eof_total 51957
telemt_me_idle_close_by_peer_total 51949
telemt_me_route_drop_no_conn_total 869256
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2044036
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4115
telemt_desync_full_logged_total 1353
telemt_desync_suppressed_total 2762
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 1681
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 192
telemt_me_writer_removed_unexpected_total 49315
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 48469
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 821
telemt_user_connections_total{user="hello"} 2050447
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 30362349467 (28.28 GB)
telemt_user_octets_to_client{user="hello"} 731191427382 (680.98 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 93687.9 (26h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1068245
telemt_connections_bad_total 18105
telemt_handshake_timeouts_total 13801
telemt_upstream_connect_attempt_total 22802
telemt_upstream_connect_success_total 22169
telemt_upstream_connect_fail_total 632
telemt_upstream_connect_attempts_per_request{bucket="1"} 22801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 632
telemt_me_keepalive_timeout_total 1789
telemt_me_reconnect_attempts_total 82535
telemt_me_reconnect_success_total 17497
telemt_me_reader_eof_total 19937
telemt_me_idle_close_by_peer_total 19936
telemt_me_route_drop_no_conn_total 432320
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 989285
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2651
telemt_desync_full_logged_total 831
telemt_desync_suppressed_total 1820
telemt_desync_frames_bucket_total{bucket="1_2"} 954
telemt_desync_frames_bucket_total{bucket="3_10"} 941
telemt_desync_frames_bucket_total{bucket="gt_10"} 756
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19688
telemt_me_refill_failed_total 2027
telemt_me_writer_restored_same_endpoint_total 17492
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2191
telemt_user_connections_total{user="hello"} 988486
telemt_user_connections_current{user="hello"} 718
telemt_user_octets_from_client{user="hello"} 17157421216 (15.98 GB)
telemt_user_octets_to_client{user="hello"} 332834580840 (309.98 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 105
```